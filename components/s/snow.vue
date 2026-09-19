<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd19m6j6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd19m6j6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:snow" /></template>
