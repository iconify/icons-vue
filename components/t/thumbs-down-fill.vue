<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzw5rib-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzw5rib-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:thumbs-down-fill" /></template>
