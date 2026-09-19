<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da1jukbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="da1jukbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:private-driver-filled" /></template>
