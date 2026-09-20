<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eibdgkb_a.css';
import '../../css/b/bk8xu6baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eibdgkb_a"/><path class="bk8xu6baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wlkn" /></template>
