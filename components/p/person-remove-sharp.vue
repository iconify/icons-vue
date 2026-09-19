<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj0h6tbsi.css';
import '../../css/k/kvfqgdcvb.css';
import '../../css/l/lpwt15b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rj0h6tbsi"/><circle class="kvfqgdcvb"/><path class="lpwt15b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:person-remove-sharp" /></template>
