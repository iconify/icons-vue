<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfiv3z6qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zfiv3z6qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mullvad-vpn-light" /></template>
