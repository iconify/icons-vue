<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moxt6ocnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="moxt6ocnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:moon" /></template>
