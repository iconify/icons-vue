<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td-iq2oif.css';
import '../../css/d/dq3pidbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td-iq2oif"/><path class="dq3pidbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:washer-filled" /></template>
