<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw55dhb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw55dhb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:signal-alt" /></template>
