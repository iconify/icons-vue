<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkxs0px9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkxs0px9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:table-1-filled" /></template>
