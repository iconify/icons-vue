<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqb36oeds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqb36oeds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pause-light" /></template>
