<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boagz7yoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="boagz7yoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrow-left-down-filled" /></template>
