<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk1ec_hjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk1ec_hjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:outdent-solid" /></template>
