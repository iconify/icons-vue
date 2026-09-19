<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq15az8iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oq15az8iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-instagram-outline" /></template>
