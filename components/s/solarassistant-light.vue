<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd2317bpb.css';
import '../../css/j/j2_dkcu_s.css';
import '../../css/r/ri_kzvb7p.css';
import '../../css/b/bdr85wbvd.css';
import '../../css/j/jzaw16b-k.css';
import '../../css/v/vlblsvc5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rd2317bpb"/><path class="j2_dkcu_s"/><path class="ri_kzvb7p"/><path class="bdr85wbvd"/><path class="jzaw16b-k"/><path class="vlblsvc5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:solarassistant-light" /></template>
