<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxh0f2bbu.css';
import '../../css/r/rqmkcsbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oxh0f2bbu"/><path class="rqmkcsbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:upload-light" /></template>
