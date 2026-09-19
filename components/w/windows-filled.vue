<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r51k3lv5c.css';
import '../../css/v/v_3i9wmxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r51k3lv5c"/><path class="v_3i9wmxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:windows-filled" /></template>
