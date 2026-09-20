<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqjmsh66x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqjmsh66x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:square-duotone" /></template>
