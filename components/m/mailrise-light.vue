<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re3lufbbf.css';
import '../../css/j/jh93d6jmw.css';
import '../../css/l/lq0ayphzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="re3lufbbf"/><path class="jh93d6jmw"/><path class="lq0ayphzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailrise-light" /></template>
