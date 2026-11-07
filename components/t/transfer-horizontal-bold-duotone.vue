<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb8a2xbld.css';
import '../../css/a/auyi_ibtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb8a2xbld"/><path class="auyi_ibtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:transfer-horizontal-bold-duotone" /></template>
