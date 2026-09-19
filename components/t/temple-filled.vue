<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkh3mii8l.css';
import '../../css/w/w4ucru71v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkh3mii8l"/><path class="w4ucru71v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:temple-filled" /></template>
