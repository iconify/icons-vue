<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti_9tgx1a.css';
import '../../css/q/qpq6tjknf.css';
import '../../css/s/su7532b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti_9tgx1a"/><path class="qpq6tjknf"/><path clip-rule="evenodd" class="su7532b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:routing-2-outline" /></template>
