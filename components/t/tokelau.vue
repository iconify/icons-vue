<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymvjmwp_c.css';
import '../../css/l/lj8m_5b8h.css';
import '../../css/d/dealb4p_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ymvjmwp_c"/><path class="lj8m_5b8h"/><path class="dealb4p_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:tokelau" /></template>
