<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znayi4bdb.css';
import '../../css/g/g8dz_qbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znayi4bdb"/><path class="g8dz_qbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:sign-out" /></template>
