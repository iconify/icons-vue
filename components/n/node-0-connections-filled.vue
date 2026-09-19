<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s98hn0ejv.css';
import '../../css/b/bqbfju-hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s98hn0ejv"/><path clip-rule="evenodd" class="bqbfju-hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:node-0-connections-filled" /></template>
