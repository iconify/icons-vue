<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5zcv1but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s5zcv1but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:necktie" /></template>
