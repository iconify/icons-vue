<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vms7zibqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vms7zibqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:orientation-landscape-solid" /></template>
