<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu91qdbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iu91qdbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tumble-dryer-filled" /></template>
