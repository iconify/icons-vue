<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nae4m6bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nae4m6bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mullvad-vpn-dark" /></template>
