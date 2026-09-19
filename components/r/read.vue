<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1aorzgmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q1aorzgmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:read" /></template>
