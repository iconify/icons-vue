<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un164r4db.css';
import '../../css/m/m_0bwy7ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="un164r4db"/><path class="m_0bwy7ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:timer-filled" /></template>
