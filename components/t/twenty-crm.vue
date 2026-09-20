<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_hh80boa.css';
import '../../css/p/p4pgybewu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v_hh80boa"/><path class="p4pgybewu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twenty-crm" /></template>
