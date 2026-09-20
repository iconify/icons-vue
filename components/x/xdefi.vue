<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1tdwcb_m.css';
import '../../css/m/m-0kq_b5b.css';
import '../../css/u/uhr3ctv0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1tdwcb_m"/><path class="m-0kq_b5b"/><path class="uhr3ctv0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xdefi" /></template>
