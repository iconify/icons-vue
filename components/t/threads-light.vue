<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bah20gb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":192};
const content = `<path class="bah20gb6v x19hqcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:threads-light" /></template>
