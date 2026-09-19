<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_zmtc4ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v_zmtc4ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:moon" /></template>
