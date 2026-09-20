<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-6i0h0fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:personal-bag-outline-sharp" /></template>
<style>
.q-6i0h0fs {
  fill: currentColor;
  d: path("M6 21v-9q0-1.933 1.084-3.425q1.083-1.492 2.762-2.144V6q0-.897.63-1.526q.63-.628 1.529-.628t1.524.628T14.154 6v.43q1.679.653 2.762 2.145Q18 10.067 18 12v9zm1-1h10v-8q0-2.075-1.463-3.537T12 7T8.463 8.463T7 12zm1.5-6.5h6v2h1v-3h-7zm2.346-7.361q.294-.07.577-.104Q11.706 6 12 6t.577.034t.577.105V6q0-.49-.336-.822q-.335-.332-.818-.332t-.818.332t-.336.822zM7 20h10z");
}

</style>
