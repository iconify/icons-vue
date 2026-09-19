<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el_-m5xbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="el_-m5xbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:servicestack" /></template>
