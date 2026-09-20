<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl55wk13u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl55wk13u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:slideshare" /></template>
