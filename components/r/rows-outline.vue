<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl5lc-bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gl5lc-bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:rows-outline" /></template>
