<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkgtonb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":192};
const content = `<path class="pkgtonb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sanity-dark" /></template>
