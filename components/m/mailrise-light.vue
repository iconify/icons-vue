<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mshnxfvng.css';
import '../../css/j/jh93d6jmw.css';
import '../../css/n/ntjhm5bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mshnxfvng"/><path class="jh93d6jmw"/><path class="ntjhm5bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mailrise-light" /></template>
