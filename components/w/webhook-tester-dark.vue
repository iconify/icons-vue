<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwv2rb7dk.css';
import '../../css/e/ejz03ub5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gwv2rb7dk"/><path class="ejz03ub5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:webhook-tester-dark" /></template>
