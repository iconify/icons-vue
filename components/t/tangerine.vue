<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g6hpcqcaw"/><path class="rohq2i4ix"/><path class="qm_xpwrlg"/><g class="txnbp1wlk"><path class="lkzk7kzon"/><path class="s23x-jbtl"/></g><path class="wtnsudbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:tangerine" /></template>
<style>
.g6hpcqcaw {
  fill: var(--svg-color--f79420, #f79420);
  d: path("M60.21 35.933c0 15.407-13.03 27.888-29.11 27.888S2 51.34 2 35.933C2 20.53 15.03 9.813 31.1 9.813c16.08 0 29.11 10.719 29.11 26.12");
}

.lkzk7kzon {
  d: path("M50.05 3.663c.016.298-1.416 1.446-1.575 1.49c-4.135 1.126-10.06 9.496-10.842 10.723c-1.805 2.84-5.265 4.676-6.119 3.247c-.829-1.376 2.2-7.756 2.761-9.06c1.374-3.194 3.941-6.416 6.741-8.488c2.952-2.191 8.78-2.594 9.03 2.09");
}

.qm_xpwrlg {
  fill: var(--svg-color--0b887e, #0b887e);
  d: path("M33.807 6.932c-1.544-1.818-8.562-.32-9.79.719c-1.227 1.047 3.17 3.418 5.436 5.02c2.336 1.647 4.617 3.431 5.841 2.388s.062-6.31-1.487-8.125");
}

.rohq2i4ix {
  fill: var(--svg-color--dc8427, #dc8427);
  d: path("M40.869 11.244c5.777 11.07 7.622 23.439 1.431 35.34c-3.892 7.484-9.196 12.655-15.292 16.928c1.343.18 2.704.307 4.095.307c16.08 0 29.11-12.48 29.11-27.888c0-12.12-8.08-21.31-19.342-24.689");
}

.s23x-jbtl {
  d: path("M43.2 12.524c3.941.009 9.551 10.46 9.548 13.12c-.009 2.66-7.69-.351-12.13-1.499c-4.571-1.188-9.257-2.156-9.251-4.816c.004-2.66 7.893-6.814 11.832-6.805");
}

.txnbp1wlk {
  fill: var(--svg-color--2bb573, #2bb573);
}

.wtnsudbsc {
  fill: var(--svg-color--04a69c, #04a69c);
  d: path("M27.293 8.816c-2.971-1.507-11.201 4.211-12.217 6.218c-1.015 2.01 5.922 2.682 9.704 3.519c3.9.859 7.8 1.923 8.814-.079c1.014-2-3.33-8.155-6.301-9.658");
}

</style>
