<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iku3gdbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iku3gdbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:plus-small-solid" /></template>
