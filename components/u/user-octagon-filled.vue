<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/texuw4bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="texuw4bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-octagon-filled" /></template>
