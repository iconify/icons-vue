<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3xg_yztz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v3xg_yztz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-cheese-wedge-hat" /></template>
