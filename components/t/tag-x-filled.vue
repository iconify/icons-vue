<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjv7a_47d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjv7a_47d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tag-x-filled" /></template>
