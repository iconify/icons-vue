<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px2gognml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px2gognml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-dollar" /></template>
