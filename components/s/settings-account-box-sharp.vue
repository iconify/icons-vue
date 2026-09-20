<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5f5lybgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-account-box-sharp" /></template>
<style>
.t5f5lybgu {
  fill: currentColor;
  d: path("M13.385 21.846v-8.461h8.461v8.461zM10.135 21l-.362-2.892q-.479-.145-1.035-.454q-.557-.31-.947-.664l-2.668 1.135l-1.865-3.25l2.306-1.739q-.045-.27-.073-.558q-.03-.288-.03-.559q0-.252.03-.53q.028-.278.073-.626L3.258 9.126l1.865-3.212L7.771 7.03q.448-.373.97-.673q.52-.3 1.013-.464L10.134 3h3.732l.361 2.912q.575.202 1.016.463t.909.654l2.725-1.115l1.865 3.211l-2.278 1.721q0 .038.009.077q.01.039.01.077h-4.237q-.292-.652-.894-1.076T11.973 9.5q-1.046 0-1.773.727T9.473 12q0 .796.416 1.408q.415.611 1.111.904V21zm4.634-.538h5.693v-.69q-.53-.633-1.275-.972q-.746-.338-1.571-.338t-1.572.338t-1.275.971zm3.746-3.217q.37-.37.37-.899t-.37-.899t-.9-.37t-.899.37t-.37.9q0 .528.37.898t.9.37q.528 0 .898-.37");
}

</style>
