<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qph_4msfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qph_4msfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:victory-finger-02" /></template>
