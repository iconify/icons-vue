<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhrz9cckz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhrz9cckz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shield-plus-filled" /></template>
