<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fza6ibbjn.css';
import '../../css/b/bazy2ab2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fza6ibbjn"/><path class="bazy2ab2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pen-edit-circle-filled" /></template>
