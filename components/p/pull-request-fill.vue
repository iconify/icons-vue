<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3g27jb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3g27jb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:pull-request-fill" /></template>
