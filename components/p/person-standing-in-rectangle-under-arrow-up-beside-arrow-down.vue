<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g25ne3b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g25ne3b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-standing-in-rectangle-under-arrow-up-beside-arrow-down" /></template>
