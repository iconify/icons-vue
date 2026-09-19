<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6j0uvbgv.css';
import '../../css/y/y7cjcccww.css';
import '../../css/u/u-6-7yubm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="u6j0uvbgv"/><path class="y7cjcccww"/><path class="u-6-7yubm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:vertx-wordmark" /></template>
