<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c128rpb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c128rpb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zensical" /></template>
