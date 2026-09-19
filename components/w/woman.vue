<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcyvurbju.css';
import '../../css/z/zy09reb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="bcyvurbju"/><path class="zy09reb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:woman" /></template>
