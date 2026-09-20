<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob9sxvbzl.css';
import '../../css/z/zfyfngbdb.css';
import '../../css/l/lnqbgixxr.css';
import '../../css/i/if99olb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ob9sxvbzl"/><path class="zfyfngbdb"/><path class="lnqbgixxr"/><path class="if99olb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:travstats" /></template>
