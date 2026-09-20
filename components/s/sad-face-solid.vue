<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkms7-b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gkms7-b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sad-face-solid" /></template>
