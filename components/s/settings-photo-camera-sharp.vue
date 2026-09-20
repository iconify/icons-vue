<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g36ohmy0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-photo-camera-sharp" /></template>
<style>
.g36ohmy0g {
  fill: currentColor;
  d: path("M13.385 21v-6.77h2.538l.846-.845h1.693l.846.846h2.538V21zm5.422-2.193q.5-.501.5-1.191t-.5-1.192t-1.191-.501q-.691 0-1.192.501t-.501 1.192t.501 1.19t1.192.502t1.19-.501M10.136 21l-.362-2.892q-.479-.145-1.035-.454q-.557-.31-.947-.664l-2.668 1.135l-1.865-3.25l2.306-1.739q-.045-.27-.073-.558q-.03-.288-.03-.559q0-.252.03-.53q.028-.278.073-.626L3.258 9.126l1.865-3.212L7.771 7.03q.448-.373.97-.673q.52-.3 1.013-.464L10.134 3h3.732l.361 2.912q.575.202 1.016.463t.909.654l2.725-1.115l1.865 3.211l-2.278 1.721q0 .038.009.077q.01.039.01.077h-4.237q-.292-.652-.894-1.076T11.973 9.5q-1.046 0-1.773.727T9.473 12q0 .796.416 1.408q.415.611 1.111.904V21z");
}

</style>
