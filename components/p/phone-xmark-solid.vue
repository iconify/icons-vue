<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2qvr34yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s2qvr34yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:phone-xmark-solid" /></template>
