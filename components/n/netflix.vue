<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sru6jndya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sru6jndya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:netflix" /></template>
