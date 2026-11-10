<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-n5qac3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-n5qac3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:nu" /></template>
