<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1s8-dbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z1s8-dbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:shop-solid" /></template>
