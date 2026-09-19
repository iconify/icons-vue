<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d27n0hbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="d27n0hbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:neuter" /></template>
