<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlf1ngy_p.css';
import '../../css/m/mw_oixbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlf1ngy_p"/><path clip-rule="evenodd" class="mw_oixbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:shop-duotone" /></template>
