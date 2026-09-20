<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y29dp-xoh.css';
import '../../css/n/n_blzqpck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y29dp-xoh"/><path class="n_blzqpck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plaaylist-minimalistic-bold" /></template>
