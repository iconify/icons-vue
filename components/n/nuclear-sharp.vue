<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7d-ndb_c.css';
import '../../css/i/if1j4p61s.css';
import '../../css/b/bqprax02h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="q7d-ndb_c"/><path class="if1j4p61s"/><path class="bqprax02h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:nuclear-sharp" /></template>
