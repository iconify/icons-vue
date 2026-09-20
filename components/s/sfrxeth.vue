<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s38dn_jaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s38dn_jaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sfrxeth" /></template>
