<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd6ddu7-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd6ddu7-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:seafile" /></template>
