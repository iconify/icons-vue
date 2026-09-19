<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5_cd4cck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b5_cd4cck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:users" /></template>
