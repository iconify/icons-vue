<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6coe0beu.css';
import '../../css/l/lboc1x51a.css';
import '../../css/c/clfv5tb8j.css';
import '../../css/a/a-5l6ub9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r6coe0beu"/><path class="lboc1x51a"/><path class="clfv5tb8j"/><path class="a-5l6ub9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sendgrid-light" /></template>
