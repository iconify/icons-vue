<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdr6idi7u.css';
import '../../css/r/rpykv1bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="sdr6idi7u"/><path class="rpykv1bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:tape-drive-solid" /></template>
