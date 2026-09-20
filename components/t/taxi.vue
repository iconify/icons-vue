<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykl61k9_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ykl61k9_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:taxi" /></template>
