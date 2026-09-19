<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzc8en32u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzc8en32u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:personal-hygiene-clean-bottle-virus" /></template>
