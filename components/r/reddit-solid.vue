<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smhbvxbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smhbvxbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:reddit-solid" /></template>
