<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic8csbqvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic8csbqvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:steamdeck" /></template>
