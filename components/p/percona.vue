<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":250};
const content = `<defs><linearGradient id="SVGyE8CMb2G" x1="50%" x2="50%" y1="0%" y2="100%"><stop offset="0%" class="zrq9vuley"/><stop offset="50.474%" class="tt3ugqzfd"/><stop offset="100%" class="u2l3jtfhr"/></linearGradient></defs><path fill="url(#SVGyE8CMb2G)" class="t4bsjy_rr"/><path class="f2josfh9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:percona" /></template>
<style>
.f2josfh9p {
  fill: var(--svg-color--fcb42f, #fcb42f);
  d: path("M171.197 127.472c0 23.59-19.123 42.713-42.713 42.713S85.77 151.062 85.77 127.472s19.124-42.713 42.714-42.713s42.713 19.123 42.713 42.713");
}

.t4bsjy_rr {
  d: path("M128 .578C57.308.578 0 56.413 0 125.29c0 43.086 22.427 81.066 56.526 103.47V125.354c-.001-.158-.023-.31-.023-.467s.022-.31.023-.468v-.877h.043c.701-40.146 32.335-72.48 71.323-72.48c39.427 0 71.388 33.052 71.388 73.825c0 40.772-31.961 73.825-71.388 73.825c-15.356 0-29.543-5.062-41.187-13.592v58.207A130.8 130.8 0 0 0 128 250c70.692 0 128-55.835 128-124.71C256 56.412 198.692.577 128 .577");
}

.tt3ugqzfd {
  stop-color: var(--svg-color--c11511, #c11511);
}

.u2l3jtfhr {
  stop-color: var(--svg-color--c11411, #c11411);
}

.zrq9vuley {
  stop-color: var(--svg-color--fbb32f, #fbb32f);
}

</style>
