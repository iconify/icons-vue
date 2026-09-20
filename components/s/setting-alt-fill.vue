<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6t7pi2ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l6t7pi2ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:setting-alt-fill" /></template>
