<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr9ub67zs.css';
import '../../css/l/lrrff2bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr9ub67zs"/><path class="lrrff2bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:signin" /></template>
