<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m22iwcsgw.css';
import '../../css/d/dg1dhqmqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m22iwcsgw"/><path class="dg1dhqmqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-path-bold-duotone" /></template>
