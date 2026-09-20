<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbfian71j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbfian71j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:wallet-detailed-line" /></template>
