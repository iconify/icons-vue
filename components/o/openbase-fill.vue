<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge-w7b-ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge-w7b-ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:openbase-fill" /></template>
