<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzm9y0mnu.css';
import '../../css/n/nxx7kub6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzm9y0mnu"/><path clip-rule="evenodd" class="nxx7kub6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:usb-filled" /></template>
