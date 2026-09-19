<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqo-8vfeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqo-8vfeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:user-outline" /></template>
