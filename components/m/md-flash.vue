<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4a7kh3gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b4a7kh3gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-flash" /></template>
