<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6s2--bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b6s2--bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:red-apple" /></template>
