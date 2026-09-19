<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui-1xdb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui-1xdb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:zattoo" /></template>
