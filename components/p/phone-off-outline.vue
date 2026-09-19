<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf4v8xbuk.css';
import '../../css/v/v8r068qjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf4v8xbuk"/><path clip-rule="evenodd" class="v8r068qjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:phone-off-outline" /></template>
