<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plz817b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plz817b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-transfer-v-filled" /></template>
