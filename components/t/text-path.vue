<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx34k9ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx34k9ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-path" /></template>
