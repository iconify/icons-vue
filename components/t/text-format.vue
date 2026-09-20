<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdzggabux.css';
import '../../css/y/y9rqo7u8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="sdzggabux"/><path class="y9rqo7u8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:text-format" /></template>
