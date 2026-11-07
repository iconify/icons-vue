<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu28wccgh.css';
import '../../css/z/zfnhitbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wu28wccgh"/><path class="zfnhitbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shop-2-bold" /></template>
