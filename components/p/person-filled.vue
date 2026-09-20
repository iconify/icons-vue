<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eguvsy.css';
import '../../css/k/kyznsp.css';
import '../../css/n/nz-btv.css';
import '../../css/s/so-from-22.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eguvsy kyznsp"/><path class="kyznsp nz-btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:person-filled" /></template>
