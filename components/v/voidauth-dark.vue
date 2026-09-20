<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5nok1bpn.css';
import '../../css/t/ty41gwbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b5nok1bpn"/><path class="ty41gwbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:voidauth-dark" /></template>
