<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er_tio5vc.css';
import '../../css/g/gwgon2blw.css';
import '../../css/d/dn4_b_blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er_tio5vc"/><path class="gwgon2blw"/><path class="dn4_b_blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sort-numeric-up" /></template>
