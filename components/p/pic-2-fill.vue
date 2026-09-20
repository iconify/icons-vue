<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb3ax495o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lb3ax495o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pic-2-fill" /></template>
