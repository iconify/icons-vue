<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okm5t4bxo.css';
import '../../css/k/kv90-5mju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="okm5t4bxo"/><path class="kv90-5mju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unifi-voucher-site" /></template>
