<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdspn4blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mdspn4blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tag-2-filled" /></template>
