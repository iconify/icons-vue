<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl0-71bkm.css';
import '../../css/s/s7e79xbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl0-71bkm"/><path class="s7e79xbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:upload-brackets-bold" /></template>
