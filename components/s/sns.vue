<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbsvaobve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bbsvaobve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sns" /></template>
