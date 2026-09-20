<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot7u5ufdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot7u5ufdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:typography-24" /></template>
