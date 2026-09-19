<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-rx0gbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y-rx0gbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:server-pbx" /></template>
