<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz47_7v9x.css';
import '../../css/n/n9qbr_l5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz47_7v9x"/><path class="n9qbr_l5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:person-cursor-24" /></template>
