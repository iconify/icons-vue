<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/str0shbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="str0shbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shirt-remix" /></template>
