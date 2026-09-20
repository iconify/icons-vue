<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7ovb7b3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ovb7b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:person-add-24" /></template>
