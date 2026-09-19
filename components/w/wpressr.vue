<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atig-hh7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="atig-hh7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:wpressr" /></template>
