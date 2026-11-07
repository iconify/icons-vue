<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prq9nybvi.css';
import '../../css/q/qmmwrfbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prq9nybvi"/><path clip-rule="evenodd" class="qmmwrfbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sleeping-square-outline" /></template>
