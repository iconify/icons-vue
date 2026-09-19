<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnk09y7es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bnk09y7es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:telescope-filled" /></template>
