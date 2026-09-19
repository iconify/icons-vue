<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agtflua3y.css';
import '../../css/b/br29imbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agtflua3y"/><path class="br29imbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:window-mac-alt" /></template>
