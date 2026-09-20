<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atgd69b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="atgd69b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:menu-endways-outline" /></template>
