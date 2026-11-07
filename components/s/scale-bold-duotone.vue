<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4w_uybke.css';
import '../../css/d/dohz_0b7q.css';
import '../../css/x/x1lme2b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4w_uybke"/><path class="dohz_0b7q"/><path class="x1lme2b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scale-bold-duotone" /></template>
